<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqbayhb7u.css';
import '../../css/v/v8kcivbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqbayhb7u"/><path class="v8kcivbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:clock" {...props}></Icon>
