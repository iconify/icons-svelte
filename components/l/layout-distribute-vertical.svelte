<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tafo6yubc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tafo6yubc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-distribute-vertical" {...props}></Icon>
