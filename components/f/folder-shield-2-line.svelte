<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjulmd4st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjulmd4st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-shield-2-line" {...props}></Icon>
