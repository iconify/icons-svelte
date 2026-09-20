<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbly2j_2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="gbly2j_2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:message-alt-f" {...props}></Icon>
