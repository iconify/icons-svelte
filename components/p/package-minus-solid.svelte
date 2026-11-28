<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab_-r-boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab_-r-boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:package-minus-solid" {...props}></Icon>
