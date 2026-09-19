<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/df0qyq2st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="df0qyq2st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:emoji-happy" {...props}></Icon>
