<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b02t79b0o.css';
import '../../css/k/k5cm0iauv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b02t79b0o"/><path class="k5cm0iauv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:couch-filled" {...props}></Icon>
