<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8e8-ty9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k8e8-ty9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:monument-fill" {...props}></Icon>
