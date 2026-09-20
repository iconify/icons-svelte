<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw4q79iux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pw4q79iux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mx-linux-logo-block" {...props}></Icon>
