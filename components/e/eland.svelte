<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9khlybqh.css';
import '../../css/n/nnwxahb5l.css';
import '../../css/h/h091qbb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9khlybqh"/><path class="nnwxahb5l"/><path class="h091qbb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:eland" {...props}></Icon>
