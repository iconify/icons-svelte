<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itrhu2bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itrhu2bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:minus-circle-outline" {...props}></Icon>
