<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nelr1hbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nelr1hbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-4-fill" {...props}></Icon>
