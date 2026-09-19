<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbilk4ndb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hbilk4ndb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:facility-group-alternate" {...props}></Icon>
