<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4-9gpbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v4-9gpbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:apps-fill" {...props}></Icon>
