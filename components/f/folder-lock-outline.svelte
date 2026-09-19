<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc0el9bce.css';
import '../../css/r/r8s95ubha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lc0el9bce"/><path class="r8s95ubha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:folder-lock-outline" {...props}></Icon>
