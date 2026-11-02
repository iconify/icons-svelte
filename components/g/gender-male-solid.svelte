<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh0pjij0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eh0pjij0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-male-solid" {...props}></Icon>
