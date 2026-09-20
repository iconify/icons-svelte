<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd9tkcbou.css';
import '../../css/g/gwgec4uya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yd9tkcbou"/><path class="gwgec4uya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:idiophone-24" {...props}></Icon>
