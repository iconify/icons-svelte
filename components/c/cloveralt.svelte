<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g--9au63c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g--9au63c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cloveralt" {...props}></Icon>
