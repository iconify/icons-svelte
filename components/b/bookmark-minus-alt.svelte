<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf19ixb5n.css';
import '../../css/t/t_qou-ite.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf19ixb5n"/><path class="t_qou-ite"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bookmark-minus-alt" {...props}></Icon>
