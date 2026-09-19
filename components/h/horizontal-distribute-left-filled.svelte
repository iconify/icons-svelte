<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m64_6gi5u.css';
import '../../css/h/hpml1nxgd.css';
import '../../css/z/zvvso5rkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m64_6gi5u"/><rect class="hpml1nxgd"/><rect class="zvvso5rkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizontal-distribute-left-filled" {...props}></Icon>
