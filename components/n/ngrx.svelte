<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-50yz2xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":478,"height":512};
const content = `<path clip-rule="evenodd" class="b-50yz2xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ngrx" {...props}></Icon>
