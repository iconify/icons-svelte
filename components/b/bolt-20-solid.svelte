<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6jcmg63q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v6jcmg63q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bolt-20-solid" {...props}></Icon>
