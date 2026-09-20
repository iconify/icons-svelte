<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpbemslgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpbemslgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:laboratory-test-stool" {...props}></Icon>
