<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j10spybrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j10spybrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-victory-fill" {...props}></Icon>
