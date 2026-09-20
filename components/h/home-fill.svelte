<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drritlt1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="drritlt1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:home-fill" {...props}></Icon>
