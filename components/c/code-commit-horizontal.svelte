<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvvoo3bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvvoo3bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-commit-horizontal" {...props}></Icon>
