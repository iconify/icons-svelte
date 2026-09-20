<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3g27jb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3g27jb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pull-request-fill" {...props}></Icon>
