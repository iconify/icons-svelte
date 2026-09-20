<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k71zbv5lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k71zbv5lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:list-ul-light" {...props}></Icon>
