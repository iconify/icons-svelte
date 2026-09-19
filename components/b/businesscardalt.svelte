<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi0a_4boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="yi0a_4boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:businesscardalt" {...props}></Icon>
