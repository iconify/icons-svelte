<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6zihcc1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z6zihcc1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:psp" {...props}></Icon>
