<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijx9o5bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijx9o5bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:list-indefinite" {...props}></Icon>
