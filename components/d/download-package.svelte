<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8dn3fbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8dn3fbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:download-package" {...props}></Icon>
