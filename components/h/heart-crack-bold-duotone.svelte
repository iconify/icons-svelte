<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-abn8bob.css';
import '../../css/x/xxbq7uh3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-abn8bob"/><path class="xxbq7uh3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:heart-crack-bold-duotone" {...props}></Icon>
