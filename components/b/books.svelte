<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4q-rebxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b4q-rebxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:books" {...props}></Icon>
