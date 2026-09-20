<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg372g3ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yg372g3ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:mastering-24" {...props}></Icon>
