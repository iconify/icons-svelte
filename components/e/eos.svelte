<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2972iihw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d2972iihw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:eos" {...props}></Icon>
