<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g77ie7akg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g77ie7akg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:cloud-slash" {...props}></Icon>
