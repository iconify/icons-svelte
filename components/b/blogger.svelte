<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b50jzdmup.css';
import '../../css/b/b1u2enx3s.css';
import '../../css/g/g3roa_mfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b50jzdmup"/><path class="b1u2enx3s"/><path class="g3roa_mfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:blogger" {...props}></Icon>
