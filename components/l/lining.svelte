<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyfuaq7jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyfuaq7jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lining" {...props}></Icon>
