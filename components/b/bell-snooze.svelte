<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kva5axb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kva5axb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:bell-snooze" {...props}></Icon>
