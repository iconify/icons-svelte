<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvx3ap5pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cvx3ap5pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:copy" {...props}></Icon>
