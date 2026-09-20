<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txei_jbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txei_jbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:performance-line" {...props}></Icon>
