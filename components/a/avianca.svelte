<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa0m7rgzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa0m7rgzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:avianca" {...props}></Icon>
