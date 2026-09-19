<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wumggdzwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wumggdzwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:personal-hygiene-clean-toothpaste" {...props}></Icon>
