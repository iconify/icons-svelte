<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/abdm64bot.css';
import '../../css/h/h7xzrib4t.css';
import '../../css/a/arhdvhtkj.css';
import '../../css/b/b0yqitbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="abdm64bot"/><path class="h7xzrib4t"/><path class="arhdvhtkj"/><path clip-rule="evenodd" class="b0yqitbma"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cat-outline" {...props}></Icon>
