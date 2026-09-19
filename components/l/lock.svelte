<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8mybrbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v8mybrbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:lock" {...props}></Icon>
