<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3xprjw7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3xprjw7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:polygon-lasso-bold" {...props}></Icon>
