<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxwvt3htn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxwvt3htn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:align-objects-top" {...props}></Icon>
