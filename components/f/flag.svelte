<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_kfb9bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_kfb9bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:flag" {...props}></Icon>
