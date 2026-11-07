<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvxlsjb-h.css';
import '../../css/a/arqscgbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvxlsjb-h"/><path clip-rule="evenodd" class="arqscgbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-heart-bold" {...props}></Icon>
