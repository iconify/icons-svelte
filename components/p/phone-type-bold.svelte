<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5j4ppxlp.css';
import '../../css/h/hwyi-sb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5j4ppxlp"/><path class="hwyi-sb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:phone-type-bold" {...props}></Icon>
