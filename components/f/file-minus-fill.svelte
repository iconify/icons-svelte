<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9db1acos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9db1acos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:file-minus-fill" {...props}></Icon>
