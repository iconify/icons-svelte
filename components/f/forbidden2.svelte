<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3bj4mojt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3bj4mojt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:forbidden2" {...props}></Icon>
