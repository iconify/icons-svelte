<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2dvf4bly.css';
import '../../css/v/vu18-_bab.css';
import '../../css/q/q_81dnb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2dvf4bly"/><path class="vu18-_bab"/><path clip-rule="evenodd" class="q_81dnb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ghost-outline" {...props}></Icon>
