<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8c4lps6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q8c4lps6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:lamp-fill" {...props}></Icon>
