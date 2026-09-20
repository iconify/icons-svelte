<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qt31z2vjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qt31z2vjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:multiple-forward-left-outline" {...props}></Icon>
