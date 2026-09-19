<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp6nr1bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sp6nr1bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:caret-up-outline" {...props}></Icon>
