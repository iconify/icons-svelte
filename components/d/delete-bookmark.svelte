<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua1c_6t9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua1c_6t9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:delete-bookmark" {...props}></Icon>
