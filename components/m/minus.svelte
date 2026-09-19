<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpjgxrz7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kpjgxrz7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:minus" {...props}></Icon>
