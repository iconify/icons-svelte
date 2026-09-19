<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qseawcbxu.css';
import '../../css/v/v_f8rsa0h.css';
import '../../css/v/vwzrdlbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qseawcbxu"/><circle class="v_f8rsa0h"/><path class="vwzrdlbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:photo-album" {...props}></Icon>
