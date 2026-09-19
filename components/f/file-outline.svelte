<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa3_kk4st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa3_kk4st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-outline" {...props}></Icon>
