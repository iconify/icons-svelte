<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzx24fbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzx24fbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:font-fill" {...props}></Icon>
