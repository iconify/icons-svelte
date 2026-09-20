<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awfpctb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awfpctb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:basket-alt-2-light" {...props}></Icon>
