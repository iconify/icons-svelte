<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faapkia6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faapkia6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-4-fill" {...props}></Icon>
