<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu70e7cqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu70e7cqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:pen" {...props}></Icon>
