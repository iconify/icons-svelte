<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha4e2vb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ha4e2vb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:delete-bookmark-remix" {...props}></Icon>
