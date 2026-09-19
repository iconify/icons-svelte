<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eupbdacvd.css';
import '../../css/d/dylllccpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eupbdacvd"/><path clip-rule="evenodd" class="dylllccpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:camera-solid" {...props}></Icon>
