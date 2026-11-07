<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbi9b4b7j.css';
import '../../css/a/atape3b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbi9b4b7j"/><path clip-rule="evenodd" class="atape3b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:banknote-bold" {...props}></Icon>
