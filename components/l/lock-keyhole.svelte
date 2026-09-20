<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/i/ino9h4bpe.css';
import '../../css/n/nxnw64b0f.css';
import '../../css/e/e5eb2xs2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="ino9h4bpe"/><rect class="nxnw64b0f"/><path class="e5eb2xs2z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:lock-keyhole" {...props}></Icon>
