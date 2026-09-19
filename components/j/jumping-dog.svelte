<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk-jqx9ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rk-jqx9ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jumping-dog" {...props}></Icon>
