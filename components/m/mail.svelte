<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cd1_v8oue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cd1_v8oue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:mail" {...props}></Icon>
