<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx7lfyb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wx7lfyb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:equal" {...props}></Icon>
