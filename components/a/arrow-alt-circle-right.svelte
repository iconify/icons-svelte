<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvqusacuk.css';
import '../../css/b/bfknv0bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvqusacuk"/><path class="bfknv0bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-alt-circle-right" {...props}></Icon>
