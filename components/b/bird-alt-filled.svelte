<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjexghgat.css';
import '../../css/m/mohe2-hat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjexghgat"/><path class="mohe2-hat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bird-alt-filled" {...props}></Icon>
