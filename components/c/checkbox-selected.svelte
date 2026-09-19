<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/def7nybhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="def7nybhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:checkbox-selected" {...props}></Icon>
