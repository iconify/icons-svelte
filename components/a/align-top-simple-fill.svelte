<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgf_6p6xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgf_6p6xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-top-simple-fill" {...props}></Icon>
