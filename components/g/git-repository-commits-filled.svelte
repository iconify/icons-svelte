<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejki_ob7b.css';
import '../../css/i/igx7fitry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejki_ob7b"/><path class="igx7fitry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:git-repository-commits-filled" {...props}></Icon>
