<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1-gn6z1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g1-gn6z1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:alipay-logo-block" {...props}></Icon>
