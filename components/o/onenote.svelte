<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_szxhbqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="m_szxhbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:onenote" {...props}></Icon>
