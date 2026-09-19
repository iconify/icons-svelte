<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvj3041mo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nvj3041mo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:eightball" {...props}></Icon>
