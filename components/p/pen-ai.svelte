<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv4pscbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv4pscbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pen-ai" {...props}></Icon>
