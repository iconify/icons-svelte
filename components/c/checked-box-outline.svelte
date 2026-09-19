<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny4kt2vec.css';
import '../../css/i/i_o33ybmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny4kt2vec"/><path class="i_o33ybmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:checked-box-outline" {...props}></Icon>
