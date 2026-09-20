<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic_tog6rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ic_tog6rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:checklist-alt" {...props}></Icon>
