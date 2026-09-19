<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp8fatbpd.css';
import '../../css/d/dlc29abjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="gp8fatbpd"/><path class="dlc29abjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:current-location" {...props}></Icon>
