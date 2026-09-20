<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb9xe1bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-6,"top":-2};
const content = `<path class="gb9xe1bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:phone" {...props}></Icon>
