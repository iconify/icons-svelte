<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwiio5fxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwiio5fxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:alipay-fill" {...props}></Icon>
