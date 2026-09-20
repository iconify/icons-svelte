<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxt1u-fiz.css';
import '../../css/q/qoxo-5byh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxt1u-fiz"/><path class="qoxo-5byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:guitar-classical-24" {...props}></Icon>
