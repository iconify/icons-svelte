<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5d26zbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5d26zbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:inbox-arrow-up" {...props}></Icon>
