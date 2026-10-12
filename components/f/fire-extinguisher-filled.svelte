<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayq_smivk.css';
import '../../css/h/ht6zbmbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ayq_smivk"/><path clip-rule="evenodd" class="ht6zbmbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:fire-extinguisher-filled" {...props}></Icon>
