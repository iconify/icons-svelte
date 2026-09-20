<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw-3q14fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw-3q14fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jhipster" {...props}></Icon>
