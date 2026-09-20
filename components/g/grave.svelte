<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvrm259vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvrm259vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grave" {...props}></Icon>
