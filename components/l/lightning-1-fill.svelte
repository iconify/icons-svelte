<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku3wncb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ku3wncb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:lightning-1-fill" {...props}></Icon>
