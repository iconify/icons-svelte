<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os6uvc61m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="os6uvc61m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:person" {...props}></Icon>
