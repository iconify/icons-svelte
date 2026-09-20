<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8eqfsbjd.css';
import '../../css/e/e-4ze4bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8eqfsbjd"/><path clip-rule="evenodd" class="e-4ze4bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:recive-square-outline" {...props}></Icon>
