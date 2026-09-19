<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz0s3k_1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yz0s3k_1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pycharm" {...props}></Icon>
