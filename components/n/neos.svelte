<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojrpslb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ojrpslb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:neos" {...props}></Icon>
