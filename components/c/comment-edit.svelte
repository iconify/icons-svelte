<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukc__5m7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukc__5m7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-edit" {...props}></Icon>
