<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djfqpfwkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djfqpfwkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevron-first" {...props}></Icon>
