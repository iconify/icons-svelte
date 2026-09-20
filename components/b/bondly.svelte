<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwqe5-bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lwqe5-bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bondly" {...props}></Icon>
