<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnmpcutlm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="nnmpcutlm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:phabricator" {...props}></Icon>
