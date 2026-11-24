<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlk96vv8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jlk96vv8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:plug-slash-solid" {...props}></Icon>
