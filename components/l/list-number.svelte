<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltj9geb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ltj9geb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:list-number" {...props}></Icon>
