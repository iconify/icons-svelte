<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_imcobsl.css';
import '../../css/t/tzb-fjbvg.css';
import '../../css/z/zxol_fymk.css';
import '../../css/c/ckhj8wq2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a_imcobsl"/><path class="tzb-fjbvg"/><path class="zxol_fymk"/><path class="ckhj8wq2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:contacts-twotone" {...props}></Icon>
